<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-tp1bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw-tp1bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:folder-open-24" {...props}></Icon>
