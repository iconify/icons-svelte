<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul6ql98hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul6ql98hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:anvil" {...props}></Icon>
