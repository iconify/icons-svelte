<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa-590b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa-590b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-check-sharp" {...props}></Icon>
