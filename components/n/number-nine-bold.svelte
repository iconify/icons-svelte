<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3d10iwra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3d10iwra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:number-nine-bold" {...props}></Icon>
