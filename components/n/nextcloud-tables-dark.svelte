<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_aaqkbpl.css';
import '../../css/u/uzefn3-hw.css';
import '../../css/n/ndep3kwgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n_aaqkbpl"/><path clip-rule="evenodd" class="uzefn3-hw"/><path clip-rule="evenodd" class="ndep3kwgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-tables-dark" {...props}></Icon>
