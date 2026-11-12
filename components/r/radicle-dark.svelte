<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzgvn4bnp.css';
import '../../css/y/y8j3udq6o.css';
import '../../css/v/vyby-xbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzgvn4bnp"/><path class="y8j3udq6o"/><path class="vyby-xbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radicle-dark" {...props}></Icon>
