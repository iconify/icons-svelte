<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy7mlyd3q.css';
import '../../css/i/iet5dccbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sy7mlyd3q"/><path class="iet5dccbc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:health-cross-duo" {...props}></Icon>
