<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buwjnd3lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="buwjnd3lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-right-e" {...props}></Icon>
