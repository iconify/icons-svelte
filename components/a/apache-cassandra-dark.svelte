<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knh3k_bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knh3k_bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-cassandra-dark" {...props}></Icon>
