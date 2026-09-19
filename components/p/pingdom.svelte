<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdyddbcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="cdyddbcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pingdom" {...props}></Icon>
