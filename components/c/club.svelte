<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9pgo_h-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9pgo_h-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:club" {...props}></Icon>
