<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft30k1bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ft30k1bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:banknote" {...props}></Icon>
