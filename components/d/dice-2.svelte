<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5kaqn3pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x5kaqn3pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:dice-2" {...props}></Icon>
