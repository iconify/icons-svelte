<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8-e8acbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-e8acbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:eye-off" {...props}></Icon>
