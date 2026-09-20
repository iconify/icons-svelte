<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p28fkv5ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p28fkv5ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:crutch-remix" {...props}></Icon>
