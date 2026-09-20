<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trx027wel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trx027wel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:purescript" {...props}></Icon>
