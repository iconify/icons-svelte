<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzy_v6bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uzy_v6bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:park-remix" {...props}></Icon>
