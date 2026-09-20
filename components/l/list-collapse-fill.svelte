<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayrup6xiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayrup6xiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-fill" {...props}></Icon>
