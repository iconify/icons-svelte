<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po02nqb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":303,"height":720};
const content = `<path class="po02nqb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:male" {...props}></Icon>
