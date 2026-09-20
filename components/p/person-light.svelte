<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_qxb9zuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_qxb9zuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:person-light" {...props}></Icon>
