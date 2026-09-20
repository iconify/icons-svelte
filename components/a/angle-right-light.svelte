<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_rxwab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_rxwab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-right-light" {...props}></Icon>
