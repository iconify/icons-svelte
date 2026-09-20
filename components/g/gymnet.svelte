<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrzv76bsu.css';
import '../../css/o/o1izntgqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrzv76bsu"/><path class="o1izntgqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gymnet" {...props}></Icon>
