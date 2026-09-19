<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2j3nbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml2j3nbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:backspace-solid" {...props}></Icon>
