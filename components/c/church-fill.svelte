<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi_s3db9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi_s3db9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:church-fill" {...props}></Icon>
