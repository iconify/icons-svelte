<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvgz1_b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvgz1_b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-expand-remix" {...props}></Icon>
