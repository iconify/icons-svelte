<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo8tknqau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo8tknqau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-minus-sharp" {...props}></Icon>
