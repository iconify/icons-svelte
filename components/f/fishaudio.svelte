<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4upzqbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4upzqbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fishaudio" {...props}></Icon>
