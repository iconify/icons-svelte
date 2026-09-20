<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh-6nid-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-6nid-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fluentd" {...props}></Icon>
