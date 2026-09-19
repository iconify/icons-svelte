<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c84wutbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c84wutbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-pull-request-arrow-right" {...props}></Icon>
