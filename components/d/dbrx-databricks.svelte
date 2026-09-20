<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlsn414jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlsn414jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dbrx-databricks" {...props}></Icon>
