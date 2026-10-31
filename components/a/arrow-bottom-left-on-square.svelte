<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb2kvcb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2kvcb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-bottom-left-on-square" {...props}></Icon>
