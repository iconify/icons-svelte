<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qykgvefws.css';
import '../../css/i/ixcmx5bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qykgvefws"/><path class="ixcmx5bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kwenta" {...props}></Icon>
