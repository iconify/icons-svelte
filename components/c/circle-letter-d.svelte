<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxqpjhp1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nxqpjhp1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-d" {...props}></Icon>
