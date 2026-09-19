<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzdcv_boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzdcv_boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-lens" {...props}></Icon>
