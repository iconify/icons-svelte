<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8gjc9qvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8gjc9qvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-100" {...props}></Icon>
