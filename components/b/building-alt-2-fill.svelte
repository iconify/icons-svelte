<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyq5_6mmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyq5_6mmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-2-fill" {...props}></Icon>
