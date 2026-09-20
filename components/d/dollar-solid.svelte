<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7x7h2bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7x7h2bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:dollar-solid" {...props}></Icon>
