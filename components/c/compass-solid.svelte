<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc6pa5cqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qc6pa5cqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:compass-solid" {...props}></Icon>
