<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etr2pwbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="etr2pwbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pills2" {...props}></Icon>
