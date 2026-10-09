<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilgp3hg6a.css';
import '../../css/a/atyhtibwr.css';
import '../../css/w/wrhqn4baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ilgp3hg6a"/><path class="atyhtibwr"/><path class="wrhqn4baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mirror-48" {...props}></Icon>
