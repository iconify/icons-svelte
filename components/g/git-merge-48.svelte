<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkzs98bzj.css';
import '../../css/a/ajl3hnenw.css';
import '../../css/f/fq_nbabag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kkzs98bzj"/><path class="ajl3hnenw"/><path class="fq_nbabag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-merge-48" {...props}></Icon>
