<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka3qc9bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka3qc9bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:cloud-upload" {...props}></Icon>
