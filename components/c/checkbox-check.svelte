<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to07rdbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to07rdbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:checkbox-check" {...props}></Icon>
