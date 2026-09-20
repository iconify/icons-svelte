<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlm3xgzsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlm3xgzsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-commit-vertical" {...props}></Icon>
