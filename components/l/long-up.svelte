<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qha6nrb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qha6nrb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-up" {...props}></Icon>
