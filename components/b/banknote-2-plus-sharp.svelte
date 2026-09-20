<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chji1lpeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chji1lpeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-plus-sharp" {...props}></Icon>
