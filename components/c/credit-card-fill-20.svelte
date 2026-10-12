<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imywpub2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="imywpub2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-fill-20" {...props}></Icon>
