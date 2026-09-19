<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odku5czbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odku5czbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-outline" {...props}></Icon>
