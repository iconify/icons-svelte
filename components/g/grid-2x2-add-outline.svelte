<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqpg69lvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqpg69lvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-add-outline" {...props}></Icon>
