<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am0io7bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am0io7bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:browse-off" {...props}></Icon>
