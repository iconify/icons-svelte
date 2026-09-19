<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agwbi96kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agwbi96kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-office-2" {...props}></Icon>
