<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc8hk8p9a.css';
import '../../css/v/v2dcsq4ql.css';
import '../../css/q/qijs0vb1u.css';
import '../../css/d/dygy2qbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="qc8hk8p9a"/><circle class="v2dcsq4ql"/><circle class="qijs0vb1u"/><path class="dygy2qbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gui" {...props}></Icon>
