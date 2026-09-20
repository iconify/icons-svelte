<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzx5mqigw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzx5mqigw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:info-circle-filled" {...props}></Icon>
