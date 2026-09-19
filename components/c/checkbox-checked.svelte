<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yonxsac1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yonxsac1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:checkbox-checked" {...props}></Icon>
