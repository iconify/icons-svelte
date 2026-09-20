<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa5kl5bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oa5kl5bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:powershell" {...props}></Icon>
