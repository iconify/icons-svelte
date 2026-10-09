<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb6dvfbbn.css';
import '../../css/a/ajl3hnenw.css';
import '../../css/k/k6canw58a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rb6dvfbbn"/><path class="ajl3hnenw"/><path class="k6canw58a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-branch-48" {...props}></Icon>
