<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6xnufbol.css';
import '../../css/j/jtlquzbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6xnufbol duoicon-primary-layer"/><path class="duoicon-secondary-layer jtlquzbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:candle" {...props}></Icon>
