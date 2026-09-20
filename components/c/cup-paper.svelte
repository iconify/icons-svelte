<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm9jhimkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sm9jhimkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cup-paper" {...props}></Icon>
