<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rokf6mb-k.css';
import '../../css/r/r875-hb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rokf6mb-k"/><path clip-rule="evenodd" class="r875-hb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:arrow-right-outline" {...props}></Icon>
