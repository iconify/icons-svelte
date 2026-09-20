<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfj8c45tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfj8c45tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:license-off" {...props}></Icon>
