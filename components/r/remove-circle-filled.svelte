<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-6su2tpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v-6su2tpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remove-circle-filled" {...props}></Icon>
