<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjz1-db4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjz1-db4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:gatsby" {...props}></Icon>
