<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb87fub2m.css';
import '../../css/i/igrgcsw-i.css';
import '../../css/a/ak8i1tnjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nb87fub2m"/><path class="igrgcsw-i"/><path class="ak8i1tnjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netgear-dark" {...props}></Icon>
