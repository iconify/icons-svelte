<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysbdvk_2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ysbdvk_2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-microsoft-office" {...props}></Icon>
