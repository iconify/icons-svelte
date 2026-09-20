<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nezlz1lnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nezlz1lnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-minus" {...props}></Icon>
