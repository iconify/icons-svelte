<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w57uk_h9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w57uk_h9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:export5" {...props}></Icon>
