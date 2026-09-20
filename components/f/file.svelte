<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqg6um-gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqg6um-gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:file" {...props}></Icon>
