<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avke9od9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avke9od9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-circle-solid" {...props}></Icon>
