<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo9hxn6zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo9hxn6zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-arrow-up-solid" {...props}></Icon>
