<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9csr3vbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o9csr3vbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:label" {...props}></Icon>
