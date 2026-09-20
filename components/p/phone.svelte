<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_ogacrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qn_ogacrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:phone" {...props}></Icon>
