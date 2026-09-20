<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de2n45bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de2n45bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:gitlab" {...props}></Icon>
