<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftuv1nbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftuv1nbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-cassandra-light" {...props}></Icon>
