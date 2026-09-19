<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywxpj4_ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ywxpj4_ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:copy-minus" {...props}></Icon>
