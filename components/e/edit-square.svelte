<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzji8fgvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzji8fgvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-square" {...props}></Icon>
