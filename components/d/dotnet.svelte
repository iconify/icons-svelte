<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afa8v5bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afa8v5bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dotnet" {...props}></Icon>
