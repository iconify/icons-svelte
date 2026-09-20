<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkr7lxyrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-3.5};
const content = `<path class="fkr7lxyrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:brush-f" {...props}></Icon>
