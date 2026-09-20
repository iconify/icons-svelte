<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amws4-btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amws4-btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:coveralls" {...props}></Icon>
