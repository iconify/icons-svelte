<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1umu_e9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1umu_e9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:grafana" {...props}></Icon>
