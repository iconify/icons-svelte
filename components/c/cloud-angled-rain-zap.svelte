<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt_urbb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt_urbb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-angled-rain-zap" {...props}></Icon>
