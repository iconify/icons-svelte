<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdq-wdb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq-wdb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:h1" {...props}></Icon>
