<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku37lsbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku37lsbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:information-square-fill" {...props}></Icon>
