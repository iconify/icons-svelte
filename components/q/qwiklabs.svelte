<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7wsicctb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7wsicctb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qwiklabs" {...props}></Icon>
