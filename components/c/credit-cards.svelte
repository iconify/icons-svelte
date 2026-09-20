<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekmfh7bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ekmfh7bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:credit-cards" {...props}></Icon>
