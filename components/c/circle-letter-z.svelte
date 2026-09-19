<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v43x_zb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v43x_zb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-z" {...props}></Icon>
