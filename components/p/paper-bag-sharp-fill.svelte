<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrbw7go1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrbw7go1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paper-bag-sharp-fill" {...props}></Icon>
