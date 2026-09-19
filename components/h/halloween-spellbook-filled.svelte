<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc56-vb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vc56-vb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-spellbook-filled" {...props}></Icon>
