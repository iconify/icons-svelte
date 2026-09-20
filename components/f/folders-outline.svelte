<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqhzav2ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqhzav2ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folders-outline" {...props}></Icon>
