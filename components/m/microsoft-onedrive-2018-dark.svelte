<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt65rufct.css';
import '../../css/l/l_uk_bbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qt65rufct"/><path class="l_uk_bbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-2018-dark" {...props}></Icon>
