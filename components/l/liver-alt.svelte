<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8i7obbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v8i7obbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:liver-alt" {...props}></Icon>
