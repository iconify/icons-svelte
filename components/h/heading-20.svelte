<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ikizbpd.css';
import '../../css/q/q_u57ubre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k8ikizbpd"/><path class="q_u57ubre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heading-20" {...props}></Icon>
