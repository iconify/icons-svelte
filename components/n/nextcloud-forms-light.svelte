<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b59d-rb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b59d-rb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-forms-light" {...props}></Icon>
