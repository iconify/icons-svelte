<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acui1gbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acui1gbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:laptop-solid" {...props}></Icon>
