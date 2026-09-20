<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6yu4cbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6yu4cbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bonfire-filled" {...props}></Icon>
