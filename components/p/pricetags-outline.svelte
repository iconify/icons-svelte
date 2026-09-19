<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b91ma1vok.css';
import '../../css/v/v7d8v5b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b91ma1vok"/><circle class="v7d8v5b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pricetags-outline" {...props}></Icon>
