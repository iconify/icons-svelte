<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zivg1ubor.css';
import '../../css/s/s3yfwobff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zivg1ubor"/><path clip-rule="evenodd" class="s3yfwobff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-close-fill" {...props}></Icon>
