<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwx5wubgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwx5wubgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:eye-snake" {...props}></Icon>
