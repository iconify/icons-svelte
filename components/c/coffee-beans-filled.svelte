<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flfbxac5m.css';
import '../../css/u/u7znvqguw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flfbxac5m"/><path class="u7znvqguw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coffee-beans-filled" {...props}></Icon>
