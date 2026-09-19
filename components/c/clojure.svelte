<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bztp34bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bztp34bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:clojure" {...props}></Icon>
