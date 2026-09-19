<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk-vg6ler.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk-vg6ler"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friendsofhue" {...props}></Icon>
