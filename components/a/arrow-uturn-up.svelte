<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfwp58bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfwp58bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-uturn-up" {...props}></Icon>
