<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ejw266b.css';
import '../../css/a/aaqvjnbzo.css';
import '../../css/g/gnyy8hb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ejw266b"/><path class="aaqvjnbzo"/><path class="gnyy8hb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:git-commit" {...props}></Icon>
