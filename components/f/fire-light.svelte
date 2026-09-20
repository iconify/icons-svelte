<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcmlopf1w.css';
import '../../css/n/nhd6537wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcmlopf1w"/><path class="nhd6537wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fire-light" {...props}></Icon>
